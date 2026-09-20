<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfm92ac7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfm92ac7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yinyang-fill" {...props}></Icon>
