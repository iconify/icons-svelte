<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uey1fclew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uey1fclew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:screenshot" {...props}></Icon>
