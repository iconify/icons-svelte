<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w06-b1bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w06-b1bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:uninstall" {...props}></Icon>
