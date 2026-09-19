<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6cqm3b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6cqm3b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:swimming-pool" {...props}></Icon>
