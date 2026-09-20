<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3m3y7bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3m3y7bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tilda-publishing" {...props}></Icon>
