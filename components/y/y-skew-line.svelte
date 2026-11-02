<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpjbh-amo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpjbh-amo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:y-skew-line" {...props}></Icon>
