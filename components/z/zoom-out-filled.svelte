<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3i6zbk6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3i6zbk6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:zoom-out-filled" {...props}></Icon>
