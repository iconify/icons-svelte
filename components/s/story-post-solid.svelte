<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2w2cs-yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2w2cs-yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:story-post-solid" {...props}></Icon>
