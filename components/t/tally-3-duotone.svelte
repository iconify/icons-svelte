<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8ybj1jlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary t8ybj1jlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-3-duotone" {...props}></Icon>
