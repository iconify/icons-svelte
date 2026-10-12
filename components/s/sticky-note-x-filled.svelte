<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9j0j5byc.css';
import '../../css/s/suv5jb35a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9j0j5byc"/><path class="suv5jb35a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sticky-note-x-filled" {...props}></Icon>
