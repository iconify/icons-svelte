<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf_ejzkya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="lf_ejzkya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:window-minimize" {...props}></Icon>
