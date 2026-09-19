<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0lb46ylk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="m0lb46ylk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:tag-one-plus" {...props}></Icon>
