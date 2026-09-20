<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/damn7dbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="damn7dbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:thumbsup-solid" {...props}></Icon>
