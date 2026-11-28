<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4d1cib_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4d1cib_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:users-lock" {...props}></Icon>
