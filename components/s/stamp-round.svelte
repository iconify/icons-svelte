<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyz-9xb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyz-9xb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stamp-round" {...props}></Icon>
