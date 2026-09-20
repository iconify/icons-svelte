<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpd7kl_ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rpd7kl_ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:teahouse-15" {...props}></Icon>
