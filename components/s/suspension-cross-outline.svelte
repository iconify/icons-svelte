<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1-4xhbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1-4xhbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suspension-cross-outline" {...props}></Icon>
