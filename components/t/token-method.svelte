<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-n2__egq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r-n2__egq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-method" {...props}></Icon>
