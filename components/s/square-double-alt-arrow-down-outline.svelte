<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sipzoccpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sipzoccpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-double-alt-arrow-down-outline" {...props}></Icon>
