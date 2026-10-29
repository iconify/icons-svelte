<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg546h7yc.css';
import '../../css/h/h0a-t_-kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg546h7yc"/><path class="h0a-t_-kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:send" {...props}></Icon>
