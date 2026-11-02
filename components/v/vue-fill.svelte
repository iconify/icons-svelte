<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sodb7pimc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sodb7pimc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vue-fill" {...props}></Icon>
