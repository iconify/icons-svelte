<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1i-jqskx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="k1i-jqskx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sort-down-solid" {...props}></Icon>
