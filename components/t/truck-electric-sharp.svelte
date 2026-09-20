<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks693thui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks693thui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-electric-sharp" {...props}></Icon>
