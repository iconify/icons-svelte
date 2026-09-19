<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcl2dvbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jcl2dvbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:whatsappalt" {...props}></Icon>
