<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoe89-bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hoe89-bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:writing-hand" {...props}></Icon>
