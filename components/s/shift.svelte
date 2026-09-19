<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efnp5n2eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="efnp5n2eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:shift" {...props}></Icon>
