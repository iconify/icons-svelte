<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9nf5g3ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9nf5g3ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-4-fill" {...props}></Icon>
