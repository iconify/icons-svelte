<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eru5y1lvr.css';
import '../../css/w/wyrob-bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eru5y1lvr"/><path class="wyrob-bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sofa-48-bold" {...props}></Icon>
