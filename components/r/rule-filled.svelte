<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elqse40db.css';
import '../../css/h/hkk3_ybhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="elqse40db"/><path class="hkk3_ybhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rule-filled" {...props}></Icon>
