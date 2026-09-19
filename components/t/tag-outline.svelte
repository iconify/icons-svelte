<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-0-x4paf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-0-x4paf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:tag-outline" {...props}></Icon>
