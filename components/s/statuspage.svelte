<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frv2dt3zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="frv2dt3zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:statuspage" {...props}></Icon>
