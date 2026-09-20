<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5kdx7b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5kdx7b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ruby-horizontal" {...props}></Icon>
