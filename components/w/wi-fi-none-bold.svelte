<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfsq0xb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfsq0xb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-none-bold" {...props}></Icon>
