<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdvjvpb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pdvjvpb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-symbol" {...props}></Icon>
