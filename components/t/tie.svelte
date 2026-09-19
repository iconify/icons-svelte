<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4_lk-lvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4_lk-lvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tie" {...props}></Icon>
