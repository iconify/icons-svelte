<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v83bsjbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v83bsjbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ryo" {...props}></Icon>
