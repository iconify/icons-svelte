<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbbc3r9uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jbbc3r9uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:share" {...props}></Icon>
