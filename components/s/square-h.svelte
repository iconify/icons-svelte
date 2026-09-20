<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvce8gnhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvce8gnhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-h" {...props}></Icon>
