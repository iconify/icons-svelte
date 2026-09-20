<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqlim6brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqlim6brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:swatch-outline" {...props}></Icon>
