<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e4rcsvbfj.css';
import '../../css/k/k5u3p5bnt.css';
import '../../css/x/xrfn3bcyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="e4rcsvbfj"/><path class="k5u3p5bnt wm-a"/><path class="xrfn3bcyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-x-duo" {...props}></Icon>
