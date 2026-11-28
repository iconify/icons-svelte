<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csdv1sb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csdv1sb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shield-gear" {...props}></Icon>
