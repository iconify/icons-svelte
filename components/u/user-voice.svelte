<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiet4yv0k.css';
import '../../css/t/tiru1tbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiet4yv0k"/><path class="tiru1tbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:user-voice" {...props}></Icon>
