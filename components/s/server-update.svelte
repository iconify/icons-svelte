<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epc7_tgau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="epc7_tgau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:server-update" {...props}></Icon>
