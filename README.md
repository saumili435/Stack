# Stack
<!DOCTYPE html>
<html>
<body>

<p>id="demo"</p>

<script>
typedef struct
{
	var top;
	var items[MAXSTK]
}
stack;
function IsEmpty(stack *)
function IsFull(stack *)
function Push(stack *,var)
function Pop(stack *)
function Display(stack *)
function main()
{
	stack s;
	var x;
	const ch='1';
	s.top=-1;
	while(ch!='4')
	{
	<?	php
	echo "<h2>Stack</h2>";
	echo "PUSH";
	echo "POP";
	echo "DISPLAY";
	echo "QUIT";
	echo " Enter your choice"
	?>
	fflush(stdin);
	switch(ch)
	{
		case '1':
		<p>"entertheelementtobepushed"</p>
		Push(&s,x);
		break;
		case '2':
		x=Pop(&s);
		<p>"Poppedelementis"</p>
		break;
		case '3':
		Display(&s);
		break;
		case '4':
		break;
		default:
		<p>"Wrongchoice"</p>
 }
 }
 }
  function IsEmpty(stack *s)
  if(s->top == -1)
  {
  	return 1;
  }
  else{
  	return 0;
  }
  function IsFull(stack *s)
  if(s->top == MAXSTK-1)
  {
  	return 1;
  }
  else{
  	return 0;
  }
  function Push(stack *s, var x)
  if(IsFull(s))
  {
  	<p>"StackFull"</p>
  	return;
  }
  s->top++;
  s->items[s->top]=x;
  }
  function Pop(stack *s,var x)
  if(IsEmpty(s))
  {
  	<p>"StackEmpty"</p>
  	}
  	x=s->items[s->top];
  	s->top--;
  	return x;
  	}
  	function Display(stack *s,var i)
  	if(IsEmpty(s))
  	{
  	<p>"StackEmpty"</p>
  	return;
  	}
  	document.getElementById("demo").innerHTML="Elements in the stack are" + for(i=s->top;i>=0;i--) + s->items[i];
  	</script>
  	
  	</body>
  	</html>
  	
  	
  	
  	
  
  
  
