<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-_z0bbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-_z0bbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sparkpost" {...props}></Icon>
