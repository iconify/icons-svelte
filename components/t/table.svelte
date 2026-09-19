<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q233av4wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q233av4wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:table" {...props}></Icon>
