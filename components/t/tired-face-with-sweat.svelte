<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmisexm3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qmisexm3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-with-sweat" {...props}></Icon>
