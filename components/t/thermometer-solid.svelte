<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e37v2-bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e37v2-bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:thermometer-solid" {...props}></Icon>
