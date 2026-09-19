<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu7m2xbxv.css';
import '../../css/v/v999jcc3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="lu7m2xbxv"/><path class="v999jcc3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:torsos-all" {...props}></Icon>
