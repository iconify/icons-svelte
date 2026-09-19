<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liowms-cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1728};
const content = `<path class="liowms-cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:wpbeginner" {...props}></Icon>
