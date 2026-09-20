<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_hxwwbci.css';
import '../../css/t/tf_hn4bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_hxwwbci"/><path class="tf_hn4bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:task-filled" {...props}></Icon>
