<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwfo2luxv.css';
import '../../css/z/z1_6pqjiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwfo2luxv"/><path class="z1_6pqjiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-off-bold-duotone" {...props}></Icon>
