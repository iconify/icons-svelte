<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp4ir1wnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dp4ir1wnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tea-cup-remix" {...props}></Icon>
