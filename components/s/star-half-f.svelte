<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf6wqpb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":19};
const content = `<path class="rf6wqpb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:star-half-f" {...props}></Icon>
