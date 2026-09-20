<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhaaw35sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nhaaw35sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wifi-disabled-remix" {...props}></Icon>
