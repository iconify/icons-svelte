<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm7nzo8xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm7nzo8xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:swap-horiz-line" {...props}></Icon>
