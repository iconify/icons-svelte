<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okqm3vb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okqm3vb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:satellite-dish-filled" {...props}></Icon>
