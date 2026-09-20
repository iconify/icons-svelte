<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfsa7m3yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfsa7m3yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:smartphone-arrow-in-right-sharp" {...props}></Icon>
