<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwbmpddhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rwbmpddhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-headset-solid" {...props}></Icon>
