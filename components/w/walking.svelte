<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px047eycd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="px047eycd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:walking" {...props}></Icon>
