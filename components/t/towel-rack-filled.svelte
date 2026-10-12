<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a56v57bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a56v57bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:towel-rack-filled" {...props}></Icon>
