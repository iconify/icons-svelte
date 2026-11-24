<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig9jrdbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ig9jrdbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:trophy-filled" {...props}></Icon>
