<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g376v7bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g376v7bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vai" {...props}></Icon>
