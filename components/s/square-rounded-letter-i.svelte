<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obtyzd1ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obtyzd1ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-i" {...props}></Icon>
