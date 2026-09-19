<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy02ujb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uy02ujb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-grid-3x2" {...props}></Icon>
