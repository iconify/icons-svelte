<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulcyjwbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ulcyjwbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:weixin-search" {...props}></Icon>
