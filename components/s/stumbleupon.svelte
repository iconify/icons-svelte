<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce_6m1h3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ce_6m1h3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stumbleupon" {...props}></Icon>
