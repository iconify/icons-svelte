<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s006mfb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s006mfb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:test-tube-diagonal-filled" {...props}></Icon>
