<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo2ohfbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oo2ohfbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:user" {...props}></Icon>
