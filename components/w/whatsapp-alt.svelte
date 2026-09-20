<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1g29-sbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1g29-sbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:whatsapp-alt" {...props}></Icon>
