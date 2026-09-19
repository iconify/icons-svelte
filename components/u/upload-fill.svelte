<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk1ieab_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk1ieab_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:upload-fill" {...props}></Icon>
