<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnwxg_aar.css';
import '../../css/v/v5-1tabpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="qnwxg_aar"/><path class="v5-1tabpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:stata" {...props}></Icon>
