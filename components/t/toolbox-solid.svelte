<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyu6yccrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dyu6yccrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:toolbox-solid" {...props}></Icon>
