<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bplkplbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bplkplbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-dashed-sharp-two-tone" {...props}></Icon>
