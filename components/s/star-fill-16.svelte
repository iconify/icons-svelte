<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6c_npbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m6c_npbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:star-fill-16" {...props}></Icon>
