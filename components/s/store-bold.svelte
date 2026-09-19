<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ax9c4lghs.css';
import '../../css/s/shh2lmd7z.css';
import '../../css/k/k0aooyyum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ax9c4lghs"/><path clip-rule="evenodd" class="shh2lmd7z"/><path clip-rule="evenodd" class="k0aooyyum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:store-bold" {...props}></Icon>
