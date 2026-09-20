<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc6bs2byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bc6bs2byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sketch-dark" {...props}></Icon>
