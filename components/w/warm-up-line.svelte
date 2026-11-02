<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5__pu5le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5__pu5le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:warm-up-line" {...props}></Icon>
