<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9v1wlnre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9v1wlnre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:upwork" {...props}></Icon>
