<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aja8p_b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aja8p_b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:signpost2-filled" {...props}></Icon>
