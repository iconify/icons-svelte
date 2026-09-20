<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3xin9bnu.css';
import '../../css/m/mqpb9vb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3xin9bnu"/><path class="mqpb9vb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-locked-filled" {...props}></Icon>
