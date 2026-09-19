<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-scx2biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d-scx2biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:stubber" {...props}></Icon>
