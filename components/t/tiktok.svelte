<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdqj09ies.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rdqj09ies"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:tiktok" {...props}></Icon>
