<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jip_zkn3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="jip_zkn3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ticket-simple" {...props}></Icon>
