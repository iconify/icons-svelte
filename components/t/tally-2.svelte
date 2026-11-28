<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4dtlig6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4dtlig6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-2" {...props}></Icon>
