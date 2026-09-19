<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkljmxq8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hkljmxq8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:storefront-outline" {...props}></Icon>
