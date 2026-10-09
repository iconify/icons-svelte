<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwhg-xbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bwhg-xbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skis-48" {...props}></Icon>
