<h1>리엑트공부</h1>

<h2>2020-05-21 공부내용 정리</h2>
<h3>Life Cycle</h3>

<h4>mountion</h4>
<pre><code>
constructor()컴포넌트 생성시
static getDerivedStateFromProps()컴포넌트 스크린 보여질때 실행
render()
componentDidMount()render 실행 이후 실행
</code></pre>


<h4>updating</h4>
<pre><code>
static getDerivedStateFromProps() render() 최초 마운트 시와 갱신 시 모두 에서 실행 직전에 실행
shouldComponentUpdate() 컴포넌트 업데이트 직전에 실행 props 또는 state 가 변경되었을 때, 재랜더링을 여부를 return 값으로 결정
render()
getSnapshotBeforeUpdate()사용안함
componentDidUpdate()업데이트 완료후 실행
</code></pre>



<h4>Unmountion</h4>
<pre><code>
componentWillUnmount() 컴포넌트가 죽을때 실행
</code></pre>
