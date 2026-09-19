<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq-j7ccmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="bq-j7ccmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:street-2" {...props}></Icon>
