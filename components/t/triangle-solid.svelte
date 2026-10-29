<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf3o_obyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf3o_obyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:triangle-solid" {...props}></Icon>
