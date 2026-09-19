<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pac9bobgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="pac9bobgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tablet-alt" {...props}></Icon>
