<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hus9mwmym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hus9mwmym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thumb-down-2-line" {...props}></Icon>
