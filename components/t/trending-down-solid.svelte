<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thiy84bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thiy84bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trending-down-solid" {...props}></Icon>
