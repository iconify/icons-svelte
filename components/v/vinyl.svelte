<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6jhh5tia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d6jhh5tia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:vinyl" {...props}></Icon>
