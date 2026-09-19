<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibnuai-km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibnuai-km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-center-filled" {...props}></Icon>
