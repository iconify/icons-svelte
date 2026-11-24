<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjna77bsx.css';
import '../../css/p/p48132bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjna77bsx"/><path clip-rule="evenodd" class="p48132bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shrimp-filled" {...props}></Icon>
