<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mazprfn9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mazprfn9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:user-minus-solid" {...props}></Icon>
