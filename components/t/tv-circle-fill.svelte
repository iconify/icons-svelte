<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0ne7ihlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="h0ne7ihlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tv-circle-fill" {...props}></Icon>
