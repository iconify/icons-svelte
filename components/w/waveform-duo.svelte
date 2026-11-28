<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l3f1u7b1b.css';
import '../../css/c/cq-m1fwut.css';
import '../../css/c/cfkicbk9n.css';
import '../../css/z/zp3kgxefn.css';
import '../../css/a/a8ofgxb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l3f1u7b1b"/><path class="cq-m1fwut"/><path class="cfkicbk9n"/><path class="zp3kgxefn"/><path class="a8ofgxb6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:waveform-duo" {...props}></Icon>
