<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxwq50j8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxwq50j8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:twitch" {...props}></Icon>
