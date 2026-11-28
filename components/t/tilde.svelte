<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbl7l1byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbl7l1byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tilde" {...props}></Icon>
