<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bse37hb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="bse37hb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-check" {...props}></Icon>
