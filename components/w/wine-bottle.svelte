<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv2j-pbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rv2j-pbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wine-bottle" {...props}></Icon>
