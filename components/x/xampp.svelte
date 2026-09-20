<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy1nasb1l.css';
import '../../css/f/fpys2ac3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy1nasb1l"/><path class="fpys2ac3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:xampp" {...props}></Icon>
