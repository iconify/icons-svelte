<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wav0n5hso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wav0n5hso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rss-line" {...props}></Icon>
