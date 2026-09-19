<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahcgfdbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ahcgfdbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:vk-alternitive" {...props}></Icon>
