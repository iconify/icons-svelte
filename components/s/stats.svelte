<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmhl6tbhb.css';
import '../../css/r/rjpl5yb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tmhl6tbhb"/><path class="rjpl5yb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:stats" {...props}></Icon>
