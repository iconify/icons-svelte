<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa4x7mbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa4x7mbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:weight-fill" {...props}></Icon>
