<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieo4nfb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieo4nfb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:timer-2-line" {...props}></Icon>
