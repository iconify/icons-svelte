<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrjmzwb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wrjmzwb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:route-duotone" {...props}></Icon>
