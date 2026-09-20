<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xct7y4b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xct7y4b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:star" {...props}></Icon>
