<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hax0k24xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hax0k24xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:screen-1-solid" {...props}></Icon>
