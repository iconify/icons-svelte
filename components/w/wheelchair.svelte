<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk1lweb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="qk1lweb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:wheelchair" {...props}></Icon>
