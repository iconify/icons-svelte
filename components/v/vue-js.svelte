<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky387gxav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ky387gxav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:vue-js" {...props}></Icon>
