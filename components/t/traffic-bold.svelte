<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk6nt8boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nk6nt8boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:traffic-bold" {...props}></Icon>
