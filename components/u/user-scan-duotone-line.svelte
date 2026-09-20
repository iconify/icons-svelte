<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o58hkebvg.css';
import '../../css/s/sq-5_fmts.css';
import '../../css/f/f3ydh4-xk.css';
import '../../css/b/b0ugci2cd.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGy0n0vefb"><g class="o58hkebvg"><path class="sq-5_fmts"/><path class="f3ydh4-xk"/><circle class="b0ugci2cd"/></g></mask></defs><path mask="url(#SVGy0n0vefb)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-scan-duotone-line" {...props}></Icon>
