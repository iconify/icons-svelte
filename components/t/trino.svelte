<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ymgrbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ymgrbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trino" {...props}></Icon>
