<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qepuh-fps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qepuh-fps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wifi-solid" {...props}></Icon>
