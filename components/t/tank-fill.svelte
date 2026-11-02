<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-ynm3bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-ynm3bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tank-fill" {...props}></Icon>
