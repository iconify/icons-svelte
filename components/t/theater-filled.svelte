<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt_6_ccuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt_6_ccuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:theater-filled" {...props}></Icon>
