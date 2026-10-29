<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm2qkko-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm2qkko-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shredder" {...props}></Icon>
