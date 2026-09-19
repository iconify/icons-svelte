<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b34h2hbbd.css';
import '../../css/m/mgf3uccoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="b34h2hbbd"/><path class="mgf3uccoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:share" {...props}></Icon>
