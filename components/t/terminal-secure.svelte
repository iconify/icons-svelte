<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmjq4kbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gmjq4kbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:terminal-secure" {...props}></Icon>
