<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd7wst1lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bd7wst1lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:user-slash-thin" {...props}></Icon>
