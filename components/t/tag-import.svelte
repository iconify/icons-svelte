<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca0if03mm.css';
import '../../css/u/uu_7gibiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ca0if03mm"/><path class="uu_7gibiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tag-import" {...props}></Icon>
