<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc8t2-v3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pc8t2-v3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:shader" {...props}></Icon>
