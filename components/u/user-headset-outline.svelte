<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsjw_-bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsjw_-bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-headset-outline" {...props}></Icon>
