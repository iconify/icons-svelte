<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueybqgfhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueybqgfhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scooter-round" {...props}></Icon>
