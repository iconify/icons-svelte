<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwhv-n0jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="fwhv-n0jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:stop-outline" {...props}></Icon>
