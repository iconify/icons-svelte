<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu0_hdbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pu0_hdbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:stop" {...props}></Icon>
