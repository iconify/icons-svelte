<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b84pof_2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b84pof_2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:sort-down" {...props}></Icon>
