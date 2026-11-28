<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzfoxkoxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzfoxkoxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:utensils-x" {...props}></Icon>
