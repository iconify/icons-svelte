<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuyt0_07p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uuyt0_07p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shield-2" {...props}></Icon>
