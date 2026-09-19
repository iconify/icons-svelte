<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hebk_l4wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hebk_l4wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:switcher-start-end" {...props}></Icon>
