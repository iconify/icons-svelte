<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwj19gb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwj19gb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:skynet" {...props}></Icon>
