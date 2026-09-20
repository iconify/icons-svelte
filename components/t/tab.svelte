<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tala_i6jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tala_i6jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tab" {...props}></Icon>
