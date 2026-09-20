<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c3f8qryzp.css';
import '../../css/y/y3vmhhbzm.css';
import '../../css/s/sc106zp3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c3f8qryzp"/><path clip-rule="evenodd" class="y3vmhhbzm"/><path class="sc106zp3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sun-duotone" {...props}></Icon>
