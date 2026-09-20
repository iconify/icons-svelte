<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8grcmjgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8grcmjgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:satdot1" {...props}></Icon>
