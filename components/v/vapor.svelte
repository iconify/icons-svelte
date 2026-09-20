<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onzvro32j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onzvro32j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vapor" {...props}></Icon>
