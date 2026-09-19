<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blzfdpb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="blzfdpb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:thumbs-down" {...props}></Icon>
