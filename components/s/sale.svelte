<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlyt45s8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlyt45s8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sale" {...props}></Icon>
