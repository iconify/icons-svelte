<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_hxwwbci.css';
import '../../css/d/dpnipcczy.css';
import '../../css/k/k23eu_bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="h_hxwwbci"/><path class="dpnipcczy"/><path class="k23eu_bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:task-setting-filled" {...props}></Icon>
