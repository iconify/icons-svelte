<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcnqc5t2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zcnqc5t2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-cursor-sharp-fill" {...props}></Icon>
