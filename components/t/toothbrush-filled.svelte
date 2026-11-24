<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a59s1vb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a59s1vb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:toothbrush-filled" {...props}></Icon>
