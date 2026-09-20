<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3l3htmku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b3l3htmku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toxophily-fill" {...props}></Icon>
