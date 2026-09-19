<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fat_nsbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fat_nsbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:short-text-outline" {...props}></Icon>
