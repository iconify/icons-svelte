<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0fo7-bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0fo7-bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:wifi" {...props}></Icon>
