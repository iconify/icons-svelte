<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckoedbb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckoedbb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:touchpad" {...props}></Icon>
