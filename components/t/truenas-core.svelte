<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gulrh0bmy.css';
import '../../css/z/z-o2jl6ao.css';
import '../../css/r/rg3jykb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gulrh0bmy"/><path class="z-o2jl6ao"/><path class="rg3jykb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:truenas-core" {...props}></Icon>
