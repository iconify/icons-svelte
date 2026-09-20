<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_hx2l-ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hx2l-ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:wave-lines" {...props}></Icon>
