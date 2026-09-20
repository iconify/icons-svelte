<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwkw4bbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uwkw4bbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shield-filled" {...props}></Icon>
