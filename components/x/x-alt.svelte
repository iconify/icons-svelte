<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcdky6nmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcdky6nmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:x-alt" {...props}></Icon>
