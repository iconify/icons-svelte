<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ashe7vbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ashe7vbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vuedotjs" {...props}></Icon>
