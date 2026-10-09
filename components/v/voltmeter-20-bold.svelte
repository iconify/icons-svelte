<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5f709d9b.css';
import '../../css/g/gapv30tqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k5f709d9b"/><path class="gapv30tqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltmeter-20-bold" {...props}></Icon>
