<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olf29kb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olf29kb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:script" {...props}></Icon>
