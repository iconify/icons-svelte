<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn-ou5dst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zn-ou5dst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sofe-dark" {...props}></Icon>
