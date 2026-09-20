<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n721h4qhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n721h4qhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort-down-filled" {...props}></Icon>
