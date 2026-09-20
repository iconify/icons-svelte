<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bffidmcoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bffidmcoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:row-horizontal-filled" {...props}></Icon>
