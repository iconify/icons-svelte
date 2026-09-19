<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_og5fbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_og5fbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shield-alt-2" {...props}></Icon>
