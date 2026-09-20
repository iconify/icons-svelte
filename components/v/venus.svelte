<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cknmu4bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cknmu4bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:venus" {...props}></Icon>
