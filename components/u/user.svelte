<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txvb3pb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1070,"height":1000};
const content = `<path class="txvb3pb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:user" {...props}></Icon>
