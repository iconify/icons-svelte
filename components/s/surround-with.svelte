<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0q9ccqak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f0q9ccqak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:surround-with" {...props}></Icon>
