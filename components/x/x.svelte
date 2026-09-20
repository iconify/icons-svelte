<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sty1tsbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sty1tsbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:x" {...props}></Icon>
