<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy21kjbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy21kjbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-align-center" {...props}></Icon>
