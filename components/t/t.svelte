<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-pecr1ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="v-pecr1ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:t" {...props}></Icon>
