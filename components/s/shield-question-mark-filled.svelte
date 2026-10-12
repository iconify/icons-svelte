<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9ch9eefp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p9ch9eefp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-question-mark-filled" {...props}></Icon>
