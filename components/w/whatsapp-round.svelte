<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hguwsyb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hguwsyb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:whatsapp-round" {...props}></Icon>
