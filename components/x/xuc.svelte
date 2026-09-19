<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqo0fw7ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xqo0fw7ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xuc" {...props}></Icon>
