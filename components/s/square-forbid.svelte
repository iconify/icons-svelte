<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0uq9y3ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0uq9y3ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-forbid" {...props}></Icon>
