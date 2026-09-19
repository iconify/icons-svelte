<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uelfz6b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uelfz6b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:worktree" {...props}></Icon>
