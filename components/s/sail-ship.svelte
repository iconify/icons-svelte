<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz0hutb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xz0hutb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sail-ship" {...props}></Icon>
