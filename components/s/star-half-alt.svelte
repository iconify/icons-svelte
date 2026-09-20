<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9qs8prwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9qs8prwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:star-half-alt" {...props}></Icon>
