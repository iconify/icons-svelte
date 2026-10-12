<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn705c-7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sn705c-7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shapes-fill-20" {...props}></Icon>
