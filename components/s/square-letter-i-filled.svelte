<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6k4rbcjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6k4rbcjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-i-filled" {...props}></Icon>
