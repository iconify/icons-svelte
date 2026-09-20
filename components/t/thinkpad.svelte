<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be9ptibte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be9ptibte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:thinkpad" {...props}></Icon>
