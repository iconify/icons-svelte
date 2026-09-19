<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgor2ducd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgor2ducd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:scan-ar" {...props}></Icon>
