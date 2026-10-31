<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwofykgms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwofykgms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-bulk-round" {...props}></Icon>
