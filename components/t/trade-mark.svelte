<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu6bp5bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="hu6bp5bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:trade-mark" {...props}></Icon>
