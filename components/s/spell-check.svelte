<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qapn1w99o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qapn1w99o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:spell-check" {...props}></Icon>
