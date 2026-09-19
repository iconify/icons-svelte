<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xicmvlq6m.css';
import '../../css/r/rbg5afbtd.css';
import '../../css/h/h48i3bcrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xicmvlq6m"/><path class="rbg5afbtd"/><path class="h48i3bcrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skip-back-outline-filled" {...props}></Icon>
