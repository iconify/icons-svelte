<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sap1rtbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sap1rtbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:send-solid" {...props}></Icon>
