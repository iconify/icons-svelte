<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy0x1-bzd.css';
import '../../css/z/z_t71ccqt.css';
import '../../css/g/glonku3gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy0x1-bzd"/><path clip-rule="evenodd" class="z_t71ccqt"/><path class="glonku3gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:view-filled" {...props}></Icon>
