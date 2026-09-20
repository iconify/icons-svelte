<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd040sb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd040sb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:waves-birds" {...props}></Icon>
