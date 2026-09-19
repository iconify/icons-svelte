<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xv9bpkifw.css';
import '../../css/o/o8cfnsgvu.css';
import '../../css/r/r6_6ugb6n.css';
import '../../css/b/b-2zktb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="bi12bsetm"><g transform="translate(3 12)" class="cuyn6tgcc"><circle class="xv9bpkifw"/><ellipse class="o8cfnsgvu"/></g><path class="r6_6ugb6n"/><path class="b-2zktb5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:trolley-error" {...props}></Icon>
