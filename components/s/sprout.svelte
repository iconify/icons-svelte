<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doie_cbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doie_cbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sprout" {...props}></Icon>
