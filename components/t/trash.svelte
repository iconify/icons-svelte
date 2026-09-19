<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h72we6b4o.css';
import '../../css/j/jycc3kbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="h72we6b4o"/><path class="jycc3kbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:trash" {...props}></Icon>
