<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofmkj9b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ofmkj9b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:viaf-square" {...props}></Icon>
