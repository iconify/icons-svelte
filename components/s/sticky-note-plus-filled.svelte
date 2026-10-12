<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcro2yo8e.css';
import '../../css/a/aju00ib0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcro2yo8e"/><path class="aju00ib0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sticky-note-plus-filled" {...props}></Icon>
