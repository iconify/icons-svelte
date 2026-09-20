<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edils5bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edils5bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:v2ex" {...props}></Icon>
