<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnn2f8bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnn2f8bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-variant-off" {...props}></Icon>
