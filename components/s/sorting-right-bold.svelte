<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7cp7ogpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7cp7ogpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sorting-right-bold" {...props}></Icon>
