<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9n5u8bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9n5u8bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sick-fill" {...props}></Icon>
