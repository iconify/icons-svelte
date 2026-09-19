<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1b4lydev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1b4lydev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tv" {...props}></Icon>
