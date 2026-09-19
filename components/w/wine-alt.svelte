<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owd41sbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owd41sbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wine-alt" {...props}></Icon>
