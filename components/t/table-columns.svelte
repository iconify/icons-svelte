<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwohe441b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwohe441b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-columns" {...props}></Icon>
