<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0v1czp6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q0v1czp6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:vim-insert-mode-16" {...props}></Icon>
