<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yfn9xdb5n.css';
import '../../css/j/jjar52fez.css';
import '../../css/k/kz1lj24gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yfn9xdb5n"/><path class="jjar52fez"/><path class="kz1lj24gh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-zoom-out-broken" {...props}></Icon>
