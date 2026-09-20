<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-2i06puf.css';
import '../../css/i/i0l09vzyb.css';
import '../../css/n/n_n679b9r.css';
import '../../css/j/jslk2fb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="n-2i06puf"/><path class="i0l09vzyb"/><path clip-rule="evenodd" class="n_n679b9r"/><path clip-rule="evenodd" class="jslk2fb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:tauri" {...props}></Icon>
