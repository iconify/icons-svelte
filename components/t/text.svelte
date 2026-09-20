<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcbh3cclu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcbh3cclu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:text" {...props}></Icon>
