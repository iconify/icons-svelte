<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afjbk-grt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afjbk-grt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shop-remove-outline" {...props}></Icon>
