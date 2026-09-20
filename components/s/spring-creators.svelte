<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uela_vuco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uela_vuco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:spring-creators" {...props}></Icon>
