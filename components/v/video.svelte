<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhyin5bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1360,"height":1000};
const content = `<path class="nhyin5bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:video" {...props}></Icon>
