<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twe8hgzxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="twe8hgzxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:signal-slash" {...props}></Icon>
