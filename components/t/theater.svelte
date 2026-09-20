<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceasido7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceasido7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:theater" {...props}></Icon>
