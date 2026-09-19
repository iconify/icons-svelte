<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh4pik2np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nh4pik2np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:trigger" {...props}></Icon>
