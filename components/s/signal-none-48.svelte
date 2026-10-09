<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqwy2slfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yqwy2slfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-none-48" {...props}></Icon>
