<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u2do932kf.css';
import '../../css/y/yjw59hceh.css';
import '../../css/c/c9x1d1b6v.css';
import '../../css/y/y2bz2-bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="u2do932kf"/><path class="yjw59hceh"/><path clip-rule="evenodd" class="c9x1d1b6v"/><path class="y2bz2-bin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:shield-1" {...props}></Icon>
