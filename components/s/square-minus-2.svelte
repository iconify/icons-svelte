<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk_28bbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk_28bbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-minus-2" {...props}></Icon>
