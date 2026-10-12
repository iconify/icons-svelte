<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7mz_hbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7mz_hbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:trash-filled" {...props}></Icon>
