<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o44nf1ilh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o44nf1ilh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-solid" {...props}></Icon>
