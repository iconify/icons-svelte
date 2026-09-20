<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k59qkab7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k59qkab7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ship-line" {...props}></Icon>
