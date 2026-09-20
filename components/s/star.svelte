<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ych6gh24j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ych6gh24j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:star" {...props}></Icon>
