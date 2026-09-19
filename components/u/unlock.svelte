<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv7ibq-3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bv7ibq-3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:unlock" {...props}></Icon>
