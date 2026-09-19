<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0_qoqb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="n0_qoqb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:video" {...props}></Icon>
