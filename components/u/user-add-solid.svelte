<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z682o3bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z682o3bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-add-solid" {...props}></Icon>
