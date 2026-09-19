<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx61tsb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="mx61tsb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:signal-1" {...props}></Icon>
