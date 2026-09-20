<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj3jhzbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj3jhzbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stumble-upon-2ing-logo" {...props}></Icon>
