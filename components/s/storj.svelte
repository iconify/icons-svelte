<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx2ahyfxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kx2ahyfxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:storj" {...props}></Icon>
