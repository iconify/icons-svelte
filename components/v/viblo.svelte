<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th3j_0vfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th3j_0vfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:viblo" {...props}></Icon>
