<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmdichbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kmdichbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-add-plus" {...props}></Icon>
