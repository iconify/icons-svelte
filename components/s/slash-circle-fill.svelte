<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5_pmkbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a5_pmkbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:slash-circle-fill" {...props}></Icon>
