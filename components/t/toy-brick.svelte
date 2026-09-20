<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeeyynbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="aeeyynbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:toy-brick" {...props}></Icon>
