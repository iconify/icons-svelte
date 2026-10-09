<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmp784cfc.css';
import '../../css/d/d6khf1dib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mmp784cfc"/><path class="d6khf1dib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spatula-20" {...props}></Icon>
