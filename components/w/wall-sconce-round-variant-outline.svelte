<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwh79xb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwh79xb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wall-sconce-round-variant-outline" {...props}></Icon>
