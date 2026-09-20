<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r10eajbbi.css';
import '../../css/z/z0mykrllt.css';
import '../../css/f/f6u8w3b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r10eajbbi"/><path class="z0mykrllt"/><rect class="f6u8w3b2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:trophy-circle" {...props}></Icon>
