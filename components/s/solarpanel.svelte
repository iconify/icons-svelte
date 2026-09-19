<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_pbrfbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="w_pbrfbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:solarpanel" {...props}></Icon>
