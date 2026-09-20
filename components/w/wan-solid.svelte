<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n30b-7l1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="n30b-7l1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wan-solid" {...props}></Icon>
