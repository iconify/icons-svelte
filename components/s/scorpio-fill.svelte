<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny-d24bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny-d24bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scorpio-fill" {...props}></Icon>
