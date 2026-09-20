<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g03cglbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g03cglbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:share" {...props}></Icon>
