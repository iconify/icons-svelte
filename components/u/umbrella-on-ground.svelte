<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk-h9b3te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sk-h9b3te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:umbrella-on-ground" {...props}></Icon>
