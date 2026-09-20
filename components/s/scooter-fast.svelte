<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgip4db9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgip4db9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:scooter-fast" {...props}></Icon>
