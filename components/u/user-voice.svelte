<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjh0piecs.css';
import '../../css/t/tiru1tbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjh0piecs"/><path class="tiru1tbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:user-voice" {...props}></Icon>
