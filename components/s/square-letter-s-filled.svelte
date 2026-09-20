<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbc7sbboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbc7sbboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-s-filled" {...props}></Icon>
