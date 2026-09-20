<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz-v30kpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qz-v30kpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:windows" {...props}></Icon>
