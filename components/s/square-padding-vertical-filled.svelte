<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2q6z77ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2q6z77ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-padding-vertical-filled" {...props}></Icon>
