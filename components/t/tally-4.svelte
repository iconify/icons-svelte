<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o99x5v3qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o99x5v3qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-4" {...props}></Icon>
