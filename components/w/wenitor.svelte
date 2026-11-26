<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xknpqhb_d.css';
import '../../css/e/eu8dnzbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<circle class="xknpqhb_d"/><path class="eu8dnzbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wenitor" {...props}></Icon>
