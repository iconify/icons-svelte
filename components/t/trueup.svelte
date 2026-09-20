<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bej_p9b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bej_p9b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trueup" {...props}></Icon>
