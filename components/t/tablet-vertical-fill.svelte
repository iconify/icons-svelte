<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq41bwuze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq41bwuze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tablet-vertical-fill" {...props}></Icon>
