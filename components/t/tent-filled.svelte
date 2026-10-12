<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq0lvb2-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kq0lvb2-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tent-filled" {...props}></Icon>
