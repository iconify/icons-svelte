<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb2wzhlwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fb2wzhlwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wallet-outline" {...props}></Icon>
