<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns2ynsrwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ns2ynsrwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sim-outline" {...props}></Icon>
