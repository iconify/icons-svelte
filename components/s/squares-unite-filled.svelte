<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh-hjpb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh-hjpb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:squares-unite-filled" {...props}></Icon>
