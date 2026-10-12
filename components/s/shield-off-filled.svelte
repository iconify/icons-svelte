<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcnrz_gkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcnrz_gkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-off-filled" {...props}></Icon>
