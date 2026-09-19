<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwy1apbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qwy1apbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:semgrep" {...props}></Icon>
