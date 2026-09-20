<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9bdq5bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l9bdq5bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:unlock-alt-solid" {...props}></Icon>
