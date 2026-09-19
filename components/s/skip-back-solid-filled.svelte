<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xicmvlq6m.css';
import '../../css/x/xh_evphpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xicmvlq6m"/><path class="xh_evphpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skip-back-solid-filled" {...props}></Icon>
