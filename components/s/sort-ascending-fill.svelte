<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-sp1cbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-sp1cbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sort-ascending-fill" {...props}></Icon>
