<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol8o5mb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol8o5mb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:silent-fill" {...props}></Icon>
