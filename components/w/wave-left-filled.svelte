<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7jug4bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7jug4bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:wave-left-filled" {...props}></Icon>
