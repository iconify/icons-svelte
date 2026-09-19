<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qga7rpbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qga7rpbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:tiktok" {...props}></Icon>
