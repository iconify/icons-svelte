<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy4y9ybpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy4y9ybpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:vuejs" {...props}></Icon>
