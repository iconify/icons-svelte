<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5c5v29kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5c5v29kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-up-04" {...props}></Icon>
