<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou09uufas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ou09uufas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:waterskiing" {...props}></Icon>
