<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heqfjacds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="heqfjacds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:vim-command-mode-16" {...props}></Icon>
