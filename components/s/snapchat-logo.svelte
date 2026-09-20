<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezfb-7blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezfb-7blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:snapchat-logo" {...props}></Icon>
