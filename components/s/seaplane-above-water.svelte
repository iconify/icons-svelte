<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glo4leblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="glo4leblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:seaplane-above-water" {...props}></Icon>
