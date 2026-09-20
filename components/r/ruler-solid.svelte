<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcc876b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dcc876b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ruler-solid" {...props}></Icon>
