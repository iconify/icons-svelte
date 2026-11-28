<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zsf9f-b0s.css';
import '../../css/a/apsfa-b9n.css';
import '../../css/m/m-v6wcb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zsf9f-b0s"/><path class="apsfa-b9n"/><path class="m-v6wcb8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:test-tube" {...props}></Icon>
