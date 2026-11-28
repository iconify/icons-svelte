<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5jdd2bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5jdd2bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ticket" {...props}></Icon>
