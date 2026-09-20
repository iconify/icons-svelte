<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwmrrac9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwmrrac9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shopping-search-outline" {...props}></Icon>
