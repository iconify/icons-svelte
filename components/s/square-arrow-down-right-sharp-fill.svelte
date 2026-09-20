<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2klubbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b2klubbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-down-right-sharp-fill" {...props}></Icon>
