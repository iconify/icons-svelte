<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7b54abma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7b54abma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:subscript-solid" {...props}></Icon>
