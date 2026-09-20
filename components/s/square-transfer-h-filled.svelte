<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt-s9mb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dt-s9mb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-transfer-h-filled" {...props}></Icon>
