<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gphtcn8kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gphtcn8kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:tally-5" {...props}></Icon>
