<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3wqkzi9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m3wqkzi9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:semantic-release" {...props}></Icon>
