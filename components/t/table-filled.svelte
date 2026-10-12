<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2tz9zcxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2tz9zcxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:table-filled" {...props}></Icon>
