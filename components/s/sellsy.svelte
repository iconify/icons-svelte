<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nekr66b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1472};
const content = `<path class="nekr66b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sellsy" {...props}></Icon>
