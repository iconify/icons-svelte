<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxxamib7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxxamib7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:twitch-fill-round" {...props}></Icon>
