<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sarag4mkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sarag4mkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:ship-line" {...props}></Icon>
