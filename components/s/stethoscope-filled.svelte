<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovcv3qbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovcv3qbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:stethoscope-filled" {...props}></Icon>
