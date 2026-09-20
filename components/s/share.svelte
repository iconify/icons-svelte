<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d46-0giua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d46-0giua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:share" {...props}></Icon>
