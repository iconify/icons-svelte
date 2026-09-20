<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1feq7vei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1feq7vei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zdotai" {...props}></Icon>
