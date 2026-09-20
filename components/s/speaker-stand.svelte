<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxk2dtb4g.css';
import '../../css/m/m9vpipbzf.css';
import '../../css/g/gnxfpjl9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxk2dtb4g"/><path class="m9vpipbzf"/><path class="gnxfpjl9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:speaker-stand" {...props}></Icon>
