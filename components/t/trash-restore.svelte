<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp8tg7byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tp8tg7byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:trash-restore" {...props}></Icon>
