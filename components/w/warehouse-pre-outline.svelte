<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stev4656k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="stev4656k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:warehouse-pre-outline" {...props}></Icon>
