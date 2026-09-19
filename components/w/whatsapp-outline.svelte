<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2llag50o.css';
import '../../css/l/lq4vgwbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2llag50o"/><path clip-rule="evenodd" class="lq4vgwbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:whatsapp-outline" {...props}></Icon>
