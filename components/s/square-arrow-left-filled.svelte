<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpkq7ob1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpkq7ob1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-arrow-left-filled" {...props}></Icon>
