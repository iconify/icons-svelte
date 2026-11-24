<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck3n3nbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck3n3nbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:unplug-filled" {...props}></Icon>
