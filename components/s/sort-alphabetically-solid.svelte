<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pju9uqsjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pju9uqsjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sort-alphabetically-solid" {...props}></Icon>
