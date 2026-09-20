<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg2-apbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg2-apbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-percentage" {...props}></Icon>
