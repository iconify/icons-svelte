<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqj5beb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqj5beb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-tennis" {...props}></Icon>
