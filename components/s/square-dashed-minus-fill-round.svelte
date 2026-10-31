<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js9x3pbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js9x3pbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-minus-fill-round" {...props}></Icon>
