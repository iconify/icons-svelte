<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdw_0vb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdw_0vb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tree-line" {...props}></Icon>
