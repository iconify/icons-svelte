<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewvesxbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewvesxbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vtho" {...props}></Icon>
