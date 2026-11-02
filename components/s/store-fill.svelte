<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziuv23_3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziuv23_3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:store-fill" {...props}></Icon>
