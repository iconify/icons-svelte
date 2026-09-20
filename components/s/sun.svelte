<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buaxhbt4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="buaxhbt4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:sun" {...props}></Icon>
