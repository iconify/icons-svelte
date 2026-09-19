<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf_wirsww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tf_wirsww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tomatocart" {...props}></Icon>
