<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvk1xwstj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zvk1xwstj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-yahoo" {...props}></Icon>
