<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utpl0q-lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utpl0q-lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:unfold-more-vertical" {...props}></Icon>
