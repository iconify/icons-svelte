<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjocleb1j.css';
import '../../css/b/b54fotqqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjocleb1j"/><path class="b54fotqqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wifi-pen-filled" {...props}></Icon>
