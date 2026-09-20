<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkygdid_m.css';
import '../../css/z/z2ukw-u9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wkygdid_m"/><path class="z2ukw-u9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:triangular-flag" {...props}></Icon>
