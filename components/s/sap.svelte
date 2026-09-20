<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxy7l51_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxy7l51_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sap" {...props}></Icon>
