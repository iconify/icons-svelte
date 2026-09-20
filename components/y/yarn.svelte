<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa_fzkb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oa_fzkb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:yarn" {...props}></Icon>
