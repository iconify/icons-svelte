<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0jokmbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v0jokmbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xdn" {...props}></Icon>
