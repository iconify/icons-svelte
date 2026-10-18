<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbxu_906s.css';
import '../../css/f/f9aktpbth.css';
import '../../css/p/p8fzstjth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vbxu_906s"/><path class="f9aktpbth"/><path class="p8fzstjth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waste-to-energy-20-bold" {...props}></Icon>
