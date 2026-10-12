<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdei6-b8p.css';
import '../../css/s/sdpl1vxew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdei6-b8p"/><path class="sdpl1vxew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-lock-filled" {...props}></Icon>
