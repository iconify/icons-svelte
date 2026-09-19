<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcrzusb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gcrzusb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:virb" {...props}></Icon>
