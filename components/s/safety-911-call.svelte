<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bde-fkg2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bde-fkg2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:safety-911-call" {...props}></Icon>
