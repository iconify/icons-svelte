<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf-lhzmoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vf-lhzmoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:triangle-left-outline" {...props}></Icon>
