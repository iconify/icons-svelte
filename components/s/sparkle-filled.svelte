<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn1b_0v6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jn1b_0v6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:sparkle-filled" {...props}></Icon>
