<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2yf3iojk.css';
import '../../css/b/bhlv4viug.css';
import '../../css/a/avwra9bwv.css';
import '../../css/x/xttyvqbqx.css';
import '../../css/d/da8bhmbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2yf3iojk wm-shadow"/><path class="bhlv4viug wm-k"/><path class="avwra9bwv wm-k"/><path class="wm-k xttyvqbqx"/><path class="da8bhmbhj wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:text-cursor" {...props}></Icon>
