<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j70k80t2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j70k80t2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-asterisk" {...props}></Icon>
