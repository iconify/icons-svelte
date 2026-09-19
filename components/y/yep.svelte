<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1b0wqoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iw1b0wqoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:yep" {...props}></Icon>
