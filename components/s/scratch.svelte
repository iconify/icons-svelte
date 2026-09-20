<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah1tjnb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah1tjnb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:scratch" {...props}></Icon>
