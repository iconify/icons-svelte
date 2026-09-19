<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3y28o36k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p3y28o36k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-settings-solid" {...props}></Icon>
