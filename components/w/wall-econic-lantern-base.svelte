<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8po4bceo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8po4bceo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-econic-lantern-base" {...props}></Icon>
