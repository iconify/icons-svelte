<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl_94nbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dl_94nbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sai" {...props}></Icon>
