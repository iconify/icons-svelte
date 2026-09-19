<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp8oo_bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp8oo_bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sunset-filled" {...props}></Icon>
