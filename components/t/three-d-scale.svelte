<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwpp8ccpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwpp8ccpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:three-d-scale" {...props}></Icon>
