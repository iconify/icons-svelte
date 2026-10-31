<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi7p1wbtw.css';
import '../../css/x/x7jq7ac9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi7p1wbtw"/><path clip-rule="evenodd" class="x7jq7ac9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-d-filled" {...props}></Icon>
