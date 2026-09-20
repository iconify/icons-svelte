<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naptvvf-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="naptvvf-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:rulers-16" {...props}></Icon>
