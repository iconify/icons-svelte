<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klivdsb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="klivdsb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:v0-vercel" {...props}></Icon>
