<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1wpnu13c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1wpnu13c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-filled" {...props}></Icon>
