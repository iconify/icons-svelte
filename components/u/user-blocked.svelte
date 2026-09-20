<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6t2-l6zm.css';
import '../../css/u/u6mx54sdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m6t2-l6zm"/><path class="u6mx54sdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-blocked" {...props}></Icon>
