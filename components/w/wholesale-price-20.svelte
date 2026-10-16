<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6og01bov.css';
import '../../css/z/zq6-sshry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6og01bov"/><path class="zq6-sshry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wholesale-price-20" {...props}></Icon>
