<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2vnijbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2vnijbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rows-3-fill" {...props}></Icon>
