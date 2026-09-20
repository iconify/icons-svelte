<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oubyt4bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oubyt4bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:select-arrow-up" {...props}></Icon>
