<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgdiet0qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgdiet0qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-u-filled" {...props}></Icon>
