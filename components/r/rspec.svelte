<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8vjs4bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k8vjs4bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rspec" {...props}></Icon>
