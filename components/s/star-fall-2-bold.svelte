<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvrwd2b_b.css';
import '../../css/f/f-cbj-b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvrwd2b_b"/><path class="f-cbj-b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-2-bold" {...props}></Icon>
