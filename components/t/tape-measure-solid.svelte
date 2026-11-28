<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohgdqu2vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohgdqu2vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tape-measure-solid" {...props}></Icon>
