<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3qe22b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3qe22b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:users" {...props}></Icon>
