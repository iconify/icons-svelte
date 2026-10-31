<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b00-xbc-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b00-xbc-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-h-filled" {...props}></Icon>
