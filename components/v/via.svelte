<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7a9fbb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t7a9fbb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:via" {...props}></Icon>
