<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whogh4bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whogh4bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-transfer-vertical-outline" {...props}></Icon>
