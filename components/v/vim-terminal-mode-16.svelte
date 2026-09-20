<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyp7mkbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dyp7mkbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:vim-terminal-mode-16" {...props}></Icon>
