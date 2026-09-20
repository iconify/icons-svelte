<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b68-ukb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b68-ukb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wifi-low-outline" {...props}></Icon>
