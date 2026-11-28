<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ilzgb1c.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zsf9f-b0s.css';
import '../../css/a/apsfa-b9n.css';
import '../../css/m/m-v6wcb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ilzgb1c secondary"/><g class="dt0cm9dhy primary"><path class="zsf9f-b0s"/><path class="apsfa-b9n"/><path class="m-v6wcb8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:test-tube-duo" {...props}></Icon>
