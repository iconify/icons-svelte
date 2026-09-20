<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0zm1bcnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0zm1bcnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:x" {...props}></Icon>
