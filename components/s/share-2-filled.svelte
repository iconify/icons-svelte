<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrf45hb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrf45hb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:share-2-filled" {...props}></Icon>
