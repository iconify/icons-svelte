<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olfdsqt4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olfdsqt4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transformation-line" {...props}></Icon>
