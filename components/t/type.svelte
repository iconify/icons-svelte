<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ov6aymbih.css';
import '../../css/j/j5qqge4bo.css';
import '../../css/s/sneccbb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ov6aymbih"/><path class="j5qqge4bo"/><path class="sneccbb6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:type" {...props}></Icon>
