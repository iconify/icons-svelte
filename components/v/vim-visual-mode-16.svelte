<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve9u0v-hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ve9u0v-hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:vim-visual-mode-16" {...props}></Icon>
