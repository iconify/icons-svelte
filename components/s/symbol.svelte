<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkdflzb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wkdflzb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:symbol" {...props}></Icon>
