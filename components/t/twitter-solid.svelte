<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpn8i3bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fpn8i3bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:twitter-solid" {...props}></Icon>
