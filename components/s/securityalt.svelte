<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-0h0cb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="g-0h0cb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:securityalt" {...props}></Icon>
