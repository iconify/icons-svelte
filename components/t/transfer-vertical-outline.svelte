<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y73vvr34y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y73vvr34y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transfer-vertical-outline" {...props}></Icon>
