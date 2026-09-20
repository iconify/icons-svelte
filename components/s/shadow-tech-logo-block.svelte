<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcskt3amy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcskt3amy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:shadow-tech-logo-block" {...props}></Icon>
