<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8-73ra6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8-73ra6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:temperature-celsius" {...props}></Icon>
