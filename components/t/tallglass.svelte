<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hczb_fq6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":1024};
const content = `<path class="hczb_fq6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tallglass" {...props}></Icon>
