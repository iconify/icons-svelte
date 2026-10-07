<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nskt8_var.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nskt8_var"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:underline" {...props}></Icon>
