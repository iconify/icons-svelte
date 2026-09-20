<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gub9fbb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gub9fbb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:user-location" {...props}></Icon>
