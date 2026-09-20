<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5g7s0cqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5g7s0cqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sound-light" {...props}></Icon>
