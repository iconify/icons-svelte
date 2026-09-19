<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abbqhab0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="abbqhab0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:terminal-git-bash" {...props}></Icon>
