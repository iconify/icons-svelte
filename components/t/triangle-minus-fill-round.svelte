<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdm-kab9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdm-kab9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-minus-fill-round" {...props}></Icon>
