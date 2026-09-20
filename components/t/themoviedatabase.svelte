<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj7670cbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj7670cbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:themoviedatabase" {...props}></Icon>
