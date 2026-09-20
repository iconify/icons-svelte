<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4wxfh01e.css';
import '../../css/n/ni-dbjlax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j4wxfh01e"/><path class="ni-dbjlax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visual-studio-code-dark" {...props}></Icon>
