<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qut7gns8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qut7gns8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:video-off-fill-round" {...props}></Icon>
