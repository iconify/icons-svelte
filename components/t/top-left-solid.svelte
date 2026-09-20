<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzv1y2bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pzv1y2bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:top-left-solid" {...props}></Icon>
