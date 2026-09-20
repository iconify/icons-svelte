<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajhzyebzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ajhzyebzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:seek-forward-16" {...props}></Icon>
