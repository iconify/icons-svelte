<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls10upb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ls10upb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:tnc" {...props}></Icon>
