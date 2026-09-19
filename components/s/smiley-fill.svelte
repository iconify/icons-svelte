<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfec_rb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vfec_rb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:smiley-fill" {...props}></Icon>
