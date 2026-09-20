<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa978s6xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-6.5};
const content = `<path class="xa978s6xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:underline" {...props}></Icon>
