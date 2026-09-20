<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdsrg8boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdsrg8boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:safe-2-line" {...props}></Icon>
