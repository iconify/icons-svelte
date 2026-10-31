<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lka41ng8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lka41ng8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shapes-fill-round" {...props}></Icon>
