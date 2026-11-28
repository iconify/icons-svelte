<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5duiv8mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b5duiv8mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:user-x-fill" {...props}></Icon>
