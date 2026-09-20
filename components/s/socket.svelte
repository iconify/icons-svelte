<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u44k2pb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u44k2pb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:socket" {...props}></Icon>
