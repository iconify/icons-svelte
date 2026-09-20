<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzwib_bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzwib_bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:temperature-full-sharp-fill" {...props}></Icon>
