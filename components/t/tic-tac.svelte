<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd6x9ya9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd6x9ya9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tic-tac" {...props}></Icon>
