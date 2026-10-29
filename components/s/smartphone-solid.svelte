<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fue8pumlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fue8pumlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smartphone-solid" {...props}></Icon>
