<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd-q15bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd-q15bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:target-fill" {...props}></Icon>
