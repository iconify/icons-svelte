<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phbn-6bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="phbn-6bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:triangle-down" {...props}></Icon>
