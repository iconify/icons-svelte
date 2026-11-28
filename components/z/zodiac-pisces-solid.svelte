<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_xfsyb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_xfsyb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-pisces-solid" {...props}></Icon>
