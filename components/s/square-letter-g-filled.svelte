<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiugnmb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kiugnmb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-g-filled" {...props}></Icon>
