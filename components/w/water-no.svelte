<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wukjsr7le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wukjsr7le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:water-no" {...props}></Icon>
