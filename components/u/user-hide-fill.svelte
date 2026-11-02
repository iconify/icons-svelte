<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2fhr3bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2fhr3bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-hide-fill" {...props}></Icon>
