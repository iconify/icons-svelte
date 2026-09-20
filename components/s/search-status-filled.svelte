<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhk07pbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhk07pbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-status-filled" {...props}></Icon>
