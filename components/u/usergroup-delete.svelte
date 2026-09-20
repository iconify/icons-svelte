<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq36g-bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xq36g-bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:usergroup-delete" {...props}></Icon>
