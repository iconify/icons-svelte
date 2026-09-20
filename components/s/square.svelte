<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb8d45bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb8d45bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:square" {...props}></Icon>
