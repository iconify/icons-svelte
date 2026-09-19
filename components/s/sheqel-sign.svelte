<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iatyzob9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="iatyzob9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sheqel-sign" {...props}></Icon>
