<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct7yciqgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ct7yciqgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:todolist" {...props}></Icon>
