<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq8b3yb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kq8b3yb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wifi-20-solid" {...props}></Icon>
