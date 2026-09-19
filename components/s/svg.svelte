<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpls246js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gpls246js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:svg" {...props}></Icon>
