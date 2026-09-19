<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzl87d67d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gzl87d67d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:stylua-ignore" {...props}></Icon>
