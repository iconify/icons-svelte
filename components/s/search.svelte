<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jozn2iebr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":740,"height":840};
const content = `<path class="jozn2iebr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:search" {...props}></Icon>
