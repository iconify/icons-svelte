<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cien864zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cien864zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:vr" {...props}></Icon>
