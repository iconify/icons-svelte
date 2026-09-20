<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewflq-bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewflq-bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:snapchat-logo" {...props}></Icon>
