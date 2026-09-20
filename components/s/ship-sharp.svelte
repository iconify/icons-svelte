<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzsqa9bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzsqa9bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ship-sharp" {...props}></Icon>
