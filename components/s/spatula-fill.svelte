<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x10pdla3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x10pdla3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spatula-fill" {...props}></Icon>
