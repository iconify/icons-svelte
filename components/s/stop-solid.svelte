<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad0xoryqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ad0xoryqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:stop-solid" {...props}></Icon>
