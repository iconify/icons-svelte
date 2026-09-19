<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7oiikgyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x7oiikgyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:telegram" {...props}></Icon>
