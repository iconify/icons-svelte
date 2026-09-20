<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dms_gtbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="dms_gtbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-down" {...props}></Icon>
