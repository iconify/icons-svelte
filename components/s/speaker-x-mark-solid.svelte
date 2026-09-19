<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4o03q_zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4o03q_zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:speaker-x-mark-solid" {...props}></Icon>
