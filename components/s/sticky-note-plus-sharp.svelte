<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l84h-5chk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l84h-5chk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sticky-note-plus-sharp" {...props}></Icon>
