<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmyjnfg9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmyjnfg9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:view-columns-2" {...props}></Icon>
