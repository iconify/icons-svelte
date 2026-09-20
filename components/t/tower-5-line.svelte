<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykuz0ccec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykuz0ccec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tower-5-line" {...props}></Icon>
