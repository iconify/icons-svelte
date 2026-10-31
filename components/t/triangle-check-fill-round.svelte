<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0895sbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0895sbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-check-fill-round" {...props}></Icon>
