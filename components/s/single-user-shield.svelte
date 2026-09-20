<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec5cx6f6r.css';
import '../../css/f/fnicxpbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ec5cx6f6r"/><path class="fnicxpbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:single-user-shield" {...props}></Icon>
