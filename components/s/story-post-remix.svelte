<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3vg96bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b3vg96bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:story-post-remix" {...props}></Icon>
