<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbdlmj-vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbdlmj-vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trusted-shops" {...props}></Icon>
