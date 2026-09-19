<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_lop9b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_lop9b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tent-filled" {...props}></Icon>
