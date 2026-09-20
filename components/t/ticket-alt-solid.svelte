<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiiq-jbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oiiq-jbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ticket-alt-solid" {...props}></Icon>
