<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac77tjbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ac77tjbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:two-arrow-in-down-up" {...props}></Icon>
