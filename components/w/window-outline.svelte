<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5smb1yju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5smb1yju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:window-outline" {...props}></Icon>
