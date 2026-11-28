<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5fda4acn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5fda4acn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tie" {...props}></Icon>
