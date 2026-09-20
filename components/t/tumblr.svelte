<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4qr4-85k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4qr4-85k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:tumblr" {...props}></Icon>
