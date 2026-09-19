<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqghkp2xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zqghkp2xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:rub" {...props}></Icon>
