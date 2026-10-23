<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a17nokbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a17nokbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:screw-filled" {...props}></Icon>
