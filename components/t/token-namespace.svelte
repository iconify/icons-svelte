<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caufp1b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="caufp1b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-namespace" {...props}></Icon>
