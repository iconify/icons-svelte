<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkwyvac_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="rkwyvac_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:theverge" {...props}></Icon>
