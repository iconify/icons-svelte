<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhb9lzbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhb9lzbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:temperature-low" {...props}></Icon>
