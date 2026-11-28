<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkle8ob3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkle8ob3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:vinyl-heart" {...props}></Icon>
