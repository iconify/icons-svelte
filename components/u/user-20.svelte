<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v891yolpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v891yolpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-20" {...props}></Icon>
