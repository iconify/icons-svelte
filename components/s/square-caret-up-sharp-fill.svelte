<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d57v2tw1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d57v2tw1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-caret-up-sharp-fill" {...props}></Icon>
