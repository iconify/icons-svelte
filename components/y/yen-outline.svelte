<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuijjsb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wuijjsb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:yen-outline" {...props}></Icon>
