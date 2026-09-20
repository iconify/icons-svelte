<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im26rieus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="im26rieus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tank-fill" {...props}></Icon>
