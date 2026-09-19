<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx2xi1jvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx2xi1jvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:volume-minus" {...props}></Icon>
