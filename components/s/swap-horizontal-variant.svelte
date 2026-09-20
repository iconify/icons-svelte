<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6-qcibcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-qcibcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:swap-horizontal-variant" {...props}></Icon>
