<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar9miut_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ar9miut_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:triangle-20-solid" {...props}></Icon>
