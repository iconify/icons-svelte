<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c561ylaaj.css';
import '../../css/g/gl5rl746c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c561ylaaj"/><path class="gl5rl746c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:zoom-in" {...props}></Icon>
