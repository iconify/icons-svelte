<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbfmdkbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bbfmdkbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:sketch-logo" {...props}></Icon>
