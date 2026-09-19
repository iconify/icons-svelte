<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtdvku_qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtdvku_qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:wine-glass" {...props}></Icon>
