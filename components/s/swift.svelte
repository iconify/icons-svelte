<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyai71m_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wyai71m_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:swift" {...props}></Icon>
