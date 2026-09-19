<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqse9p3cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":286,"height":512};
const content = `<path class="eqse9p3cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sparc" {...props}></Icon>
