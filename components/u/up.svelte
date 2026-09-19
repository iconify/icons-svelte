<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz01vrbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":448};
const content = `<path class="oz01vrbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:up" {...props}></Icon>
