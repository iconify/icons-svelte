<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0qw0kh2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h0qw0kh2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:sun" {...props}></Icon>
