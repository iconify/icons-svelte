<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px3jhzhnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="px3jhzhnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:salealt" {...props}></Icon>
