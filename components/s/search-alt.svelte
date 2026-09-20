<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc8bcyg6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bc8bcyg6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:search-alt" {...props}></Icon>
