<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvb81pbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvb81pbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:snapcraft" {...props}></Icon>
