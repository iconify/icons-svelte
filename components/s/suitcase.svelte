<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov51f8b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="ov51f8b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:suitcase" {...props}></Icon>
