<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yahrr0snd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yahrr0snd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:search-plus" {...props}></Icon>
