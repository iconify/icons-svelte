<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zur5ywbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zur5ywbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:verified" {...props}></Icon>
