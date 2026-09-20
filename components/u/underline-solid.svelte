<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9705yb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="m9705yb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:underline-solid" {...props}></Icon>
