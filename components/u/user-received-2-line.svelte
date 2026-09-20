<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeuan0b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeuan0b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-received-2-line" {...props}></Icon>
