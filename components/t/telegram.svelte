<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dunl5u65t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="dunl5u65t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:telegram" {...props}></Icon>
