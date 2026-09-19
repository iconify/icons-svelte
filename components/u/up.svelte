<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wms074r1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":614};
const content = `<path class="wms074r1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:up" {...props}></Icon>
