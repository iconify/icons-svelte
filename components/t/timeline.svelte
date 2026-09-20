<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlqrdgb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlqrdgb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:timeline" {...props}></Icon>
