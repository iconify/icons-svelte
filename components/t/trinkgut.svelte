<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtmnc00av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtmnc00av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:trinkgut" {...props}></Icon>
