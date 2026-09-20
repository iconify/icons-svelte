<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbd42ygua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wbd42ygua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:tiktok-flat" {...props}></Icon>
