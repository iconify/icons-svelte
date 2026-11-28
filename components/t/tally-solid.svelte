<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhfq9qt_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhfq9qt_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-solid" {...props}></Icon>
