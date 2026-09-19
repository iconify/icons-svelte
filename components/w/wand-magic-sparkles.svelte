<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f583vc79d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="f583vc79d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:wand-magic-sparkles" {...props}></Icon>
