<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgum38bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kgum38bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:wattpad" {...props}></Icon>
