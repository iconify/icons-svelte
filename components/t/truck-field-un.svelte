<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqdj_sbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gqdj_sbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:truck-field-un" {...props}></Icon>
