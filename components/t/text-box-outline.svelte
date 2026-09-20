<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp5g3kjqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp5g3kjqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-box-outline" {...props}></Icon>
