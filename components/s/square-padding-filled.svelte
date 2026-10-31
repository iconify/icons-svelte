<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3hc51bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x3hc51bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-padding-filled" {...props}></Icon>
