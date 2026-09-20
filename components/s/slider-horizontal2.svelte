<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld5r8bbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld5r8bbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider-horizontal2" {...props}></Icon>
