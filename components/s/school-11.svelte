<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5hfmr3-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="e5hfmr3-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:school-11" {...props}></Icon>
