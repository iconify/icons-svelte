<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2s9hnitm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u2s9hnitm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:stack" {...props}></Icon>
