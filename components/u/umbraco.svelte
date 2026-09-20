<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efg_z3lhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efg_z3lhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:umbraco" {...props}></Icon>
