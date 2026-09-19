<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_h7uab0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="k_h7uab0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:worktree-small" {...props}></Icon>
