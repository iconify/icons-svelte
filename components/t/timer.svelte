<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uq-0iysrl.css';
import '../../css/a/aawwu-mdm.css';
import '../../css/y/y4hrchb5w.css';
import '../../css/f/fyzrulpdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="uq-0iysrl"/><path class="aawwu-mdm"/><path class="y4hrchb5w"/><path class="fyzrulpdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:timer" {...props}></Icon>
