<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcvs5vdpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcvs5vdpy primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:star-off-duotone" {...props}></Icon>
