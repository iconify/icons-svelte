<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3xin9bnu.css';
import '../../css/x/xgych6eaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3xin9bnu"/><path class="xgych6eaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-unlocked-filled" {...props}></Icon>
