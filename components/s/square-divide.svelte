<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctu-0cbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctu-0cbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-divide" {...props}></Icon>
