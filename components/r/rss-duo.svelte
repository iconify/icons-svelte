<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yv4o3c3fe.css';
import '../../css/z/zrlq-ko1s.css';
import '../../css/e/em4jlpe0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yv4o3c3fe"/><path class="zrlq-ko1s"/><path class="em4jlpe0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rss-duo" {...props}></Icon>
