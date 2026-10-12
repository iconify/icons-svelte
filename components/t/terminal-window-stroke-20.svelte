<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afub65bxw.css';
import '../../css/k/kfsq47nik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="afub65bxw"/><path class="kfsq47nik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-window-stroke-20" {...props}></Icon>
