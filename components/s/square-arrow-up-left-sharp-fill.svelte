<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-0n92z7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k-0n92z7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-up-left-sharp-fill" {...props}></Icon>
