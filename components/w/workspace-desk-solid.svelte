<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3sldgb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3sldgb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:workspace-desk-solid" {...props}></Icon>
