<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au417ft5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au417ft5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:vk" {...props}></Icon>
