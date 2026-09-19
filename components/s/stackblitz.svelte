<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt7ggacqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gt7ggacqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:stackblitz" {...props}></Icon>
