<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5gp646jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5gp646jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sofa-gloss" {...props}></Icon>
