<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk_6lline.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk_6lline"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:swatch-line" {...props}></Icon>
