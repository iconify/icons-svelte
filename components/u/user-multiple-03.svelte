<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfxctf48l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfxctf48l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-multiple-03" {...props}></Icon>
