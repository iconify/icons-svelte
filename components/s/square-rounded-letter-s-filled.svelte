<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs1mzqurt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs1mzqurt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-s-filled" {...props}></Icon>
