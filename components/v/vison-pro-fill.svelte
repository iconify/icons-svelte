<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwzv0hb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jwzv0hb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vison-pro-fill" {...props}></Icon>
