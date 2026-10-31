<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am65ighor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am65ighor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-plus-round" {...props}></Icon>
