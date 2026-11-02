<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hohvgli-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hohvgli-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-flash-fill" {...props}></Icon>
