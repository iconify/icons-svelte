<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/px411qbye.css';
import '../../css/m/mobfej3oa.css';
import '../../css/n/nmxnfxicr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="px411qbye"/><path class="mobfej3oa"/><path class="nmxnfxicr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sort-amount-up" {...props}></Icon>
