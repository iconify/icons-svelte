<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa-h6knvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa-h6knvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tickets-filled" {...props}></Icon>
