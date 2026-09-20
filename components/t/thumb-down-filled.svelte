<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t678rlftl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t678rlftl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:thumb-down-filled" {...props}></Icon>
