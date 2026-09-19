<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o353a9box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o353a9box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:sort-horizontal-outline" {...props}></Icon>
