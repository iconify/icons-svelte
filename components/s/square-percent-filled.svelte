<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml22co8ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ml22co8ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-percent-filled" {...props}></Icon>
