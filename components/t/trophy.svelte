<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de84vab6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":32};
const content = `<path class="de84vab6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:trophy" {...props}></Icon>
