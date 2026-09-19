<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtr9qyb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dtr9qyb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:us-dollar" {...props}></Icon>
