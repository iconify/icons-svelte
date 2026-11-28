<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bte9woctn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bte9woctn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tea-cup-heart" {...props}></Icon>
