<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbh9_3bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cbh9_3bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:semgrep-ignore" {...props}></Icon>
