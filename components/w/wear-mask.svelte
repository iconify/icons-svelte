<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zju665b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zju665b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wear-mask" {...props}></Icon>
