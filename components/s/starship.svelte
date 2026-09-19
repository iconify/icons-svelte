<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmqd7lb1z.css';
import '../../css/s/s6x7m9trg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<defs><mask id="SVGcVHSkeyt" maskUnits="userSpaceOnUse"><circle class="nmqd7lb1z"/></mask></defs><path mask="url(#SVGcVHSkeyt)" class="s6x7m9trg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:starship" {...props}></Icon>
