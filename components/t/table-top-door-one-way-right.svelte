<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z66fxfbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="z66fxfbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-door-one-way-right" {...props}></Icon>
