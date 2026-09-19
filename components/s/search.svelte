<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv2n_6bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nv2n_6bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:search" {...props}></Icon>
