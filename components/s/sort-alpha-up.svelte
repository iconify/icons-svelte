<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb2e_5bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="pb2e_5bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-alpha-up" {...props}></Icon>
