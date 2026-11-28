<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whza9ob6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whza9ob6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-split-horizontal-solid" {...props}></Icon>
