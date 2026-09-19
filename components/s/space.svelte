<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp0hb03lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp0hb03lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:space" {...props}></Icon>
