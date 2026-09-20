<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awn78gbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="awn78gbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:suggestion-ai" {...props}></Icon>
