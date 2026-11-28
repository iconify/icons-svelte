<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa55io0tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa55io0tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:scale" {...props}></Icon>
