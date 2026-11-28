<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwl9-0qxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fwl9-0qxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-overflow-bold" {...props}></Icon>
