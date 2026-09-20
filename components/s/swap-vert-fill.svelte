<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbibiqwmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbibiqwmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:swap-vert-fill" {...props}></Icon>
