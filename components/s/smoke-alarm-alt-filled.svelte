<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fduuw1b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fduuw1b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:smoke-alarm-alt-filled" {...props}></Icon>
