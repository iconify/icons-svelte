<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyfpm4n7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hyfpm4n7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:switch-vertical" {...props}></Icon>
