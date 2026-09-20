<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktu5yu9_t.css';
import '../../css/i/iwm0m9oaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ktu5yu9_t"/><path class="iwm0m9oaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:snippet-16" {...props}></Icon>
