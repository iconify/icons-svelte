<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/n/nlnol9hhk.css';
import '../../css/z/zx2_eugjs.css';
import '../../css/e/e41hsswqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlnol9hhk"/><circle class="zx2_eugjs"/><path class="e41hsswqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-minus-01" {...props}></Icon>
