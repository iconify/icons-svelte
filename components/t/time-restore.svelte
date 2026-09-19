<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n02cxkblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":384};
const content = `<path class="n02cxkblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:time-restore" {...props}></Icon>
