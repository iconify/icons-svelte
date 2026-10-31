<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf5ttjbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf5ttjbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tennis-ball-fill-round" {...props}></Icon>
