<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrb7pj6bi.css';
import '../../css/e/ekdd0gbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":116.5,"height":62.2};
const content = `<path class="lrb7pj6bi"/><path class="ekdd0gbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:russian-railways-dark" {...props}></Icon>
