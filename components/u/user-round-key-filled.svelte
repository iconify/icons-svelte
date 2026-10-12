<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi8i8d0dt.css';
import '../../css/m/mgrdfsbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi8i8d0dt"/><path clip-rule="evenodd" class="mgrdfsbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-key-filled" {...props}></Icon>
