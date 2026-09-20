<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v28a9t3ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v28a9t3ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:view-files-16" {...props}></Icon>
