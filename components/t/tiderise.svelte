<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mll9oyleq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="mll9oyleq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tiderise" {...props}></Icon>
