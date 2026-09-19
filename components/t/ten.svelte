<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqf8rbc7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yqf8rbc7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ten" {...props}></Icon>
