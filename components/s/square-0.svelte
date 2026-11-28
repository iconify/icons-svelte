<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc6v5ibmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc6v5ibmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-0" {...props}></Icon>
