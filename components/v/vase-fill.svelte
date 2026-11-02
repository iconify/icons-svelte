<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-2z779fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-2z779fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vase-fill" {...props}></Icon>
