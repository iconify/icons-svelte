<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsa_8obst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsa_8obst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skateboard" {...props}></Icon>
