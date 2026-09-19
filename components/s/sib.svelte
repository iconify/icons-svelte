<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjsyi-n3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gjsyi-n3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sib" {...props}></Icon>
