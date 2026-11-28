<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jm7eamb2t.css';
import '../../css/h/h8yfof3aj.css';
import '../../css/w/wwl9hc22u.css';
import '../../css/x/xdws30brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jm7eamb2t"/><path class="h8yfof3aj"/><path class="wwl9hc22u"/><path class="xdws30brv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:volume-knob" {...props}></Icon>
