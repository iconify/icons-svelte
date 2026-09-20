<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjoyhab7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qjoyhab7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wifi-none-outline" {...props}></Icon>
