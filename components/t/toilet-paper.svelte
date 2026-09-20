<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-4h7cbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-4h7cbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:toilet-paper" {...props}></Icon>
