<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fchbuq2ke.css';
import '../../css/f/fvgh-ccoe.css';
import '../../css/g/g4zs08s-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fchbuq2ke"/><path class="fvgh-ccoe"/><path class="g4zs08s-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:six-circle" {...props}></Icon>
