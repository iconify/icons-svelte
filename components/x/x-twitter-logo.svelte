<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqxajmb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqxajmb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:x-twitter-logo" {...props}></Icon>
