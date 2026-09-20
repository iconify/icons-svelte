<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn5s0kk9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nn5s0kk9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-triangle-up" {...props}></Icon>
