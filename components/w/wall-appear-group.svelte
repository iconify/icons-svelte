<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7paadc1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7paadc1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-appear-group" {...props}></Icon>
