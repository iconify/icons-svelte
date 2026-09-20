<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5jr0cbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t5jr0cbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:shopware" {...props}></Icon>
