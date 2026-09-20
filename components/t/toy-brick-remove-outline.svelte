<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4445716p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4445716p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toy-brick-remove-outline" {...props}></Icon>
