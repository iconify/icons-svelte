<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9xcmbtdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x9xcmbtdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-divide-filled" {...props}></Icon>
