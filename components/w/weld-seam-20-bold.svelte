<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/escqflblo.css';
import '../../css/o/otychb1vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="escqflblo"/><path class="otychb1vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:weld-seam-20-bold" {...props}></Icon>
