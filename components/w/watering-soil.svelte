<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl6-5w16k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl6-5w16k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:watering-soil" {...props}></Icon>
