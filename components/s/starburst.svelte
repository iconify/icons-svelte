<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u97tlmbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u97tlmbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:starburst" {...props}></Icon>
