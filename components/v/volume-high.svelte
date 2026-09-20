<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9e1ynblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9e1ynblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:volume-high" {...props}></Icon>
