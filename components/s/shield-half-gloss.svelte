<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb6olbqax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb6olbqax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-half-gloss" {...props}></Icon>
