<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mab-c7got.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mab-c7got"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wifi-off" {...props}></Icon>
