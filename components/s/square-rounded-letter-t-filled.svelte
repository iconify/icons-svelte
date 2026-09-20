<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8961_5of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8961_5of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-t-filled" {...props}></Icon>
